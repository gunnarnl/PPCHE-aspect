# Aspectual constructions in ME

In matrix contexts:

Generally flat, verbal elements immediately dominated by IP-MAT, which is what we want to stick to.

We only want active matrix clauses with lexical verbs. Let's ignore things like *do*, *be*, *have*, etc.

ME has untensed modal verbs which can be main verbs. They're marked MD0, and we will ignore them. We also ignore topicalization structures which involve a VP projection which is usually absent.

Perfect: HV\* + VBN (plus optional MDs)
Progressive: BE\* + VAG (plus optional MDs)
Past: VBD
Present: VBP
Modal: MD + VB

We probably also want to pick up particles marked with RP.

There are 120 cases of a progressive perfect construction, defined in what follows. (Need to negate sisterhood in PROG and PRF alone then.)

PROG: `/^.*$/=vb [!< /^.*$/ & >+(@VAG) (@VAG > IP-MAT & $ /BE.?/=be & !$ /HV.?/ & ?$ /.*-TMP/=tmp & ?$ MD=md)] : ID=id"`

PRF: `/^.*$/=vb [!< /^.*$/ & >+(@VBN) (@VBN > IP-MAT & $ /HV.?/=hv & ?$ /.*-TMP/=tmp & ?$ MD=md)] : ID=id`

PROG+PRF: `/^.*$/=vb [!< /^.*$/ & >+(@VAG) (@VAG > IP-MAT & $ /BE.?/=be & $ /HV.?/=hv & ?$ /.*-TMP/=tmp & ?$ MD=md)] : ID=id"`


## Checking weirdness in VBP

Checking if VBP is sister to anything weird: `/^.*$/=vb [!< /^.*$/ & >+(@VBP) (@VBP > IP-MAT & $ @MD|MD0|BE|BED|BEP|BEN|BAG|BEI|DAG|DAN|DO|DOD|DOI|DON|DOP|HAG|HAN|HV|HVP|HVD|HVN|HVI|VBP|VAG|VAN|VB|VBN|VBD|VBP|VBI)]`

Most of these results are from ME and are basically "+tonked wur+de him" *thanked may he be* or a similar optative. (VAN sister to VBP)

Ignoring VAN sisters yields 6 other sentences. Some are likely misparsed and shouldn't be clausemates. They can probably be ignored too.

## Checking weirdness in VBD

Checking if VBD is sister to anything weird: `/^.*$/=vb [!< /^.*$/ & >+(@VBD) (@VBD > IP-MAT & $ @MD|MD0|BE|BED|BEP|BEN|BAG|BEI|DAG|DAN|DO|DOD|DOI|DON|DOP|HAG|HAN|HV|HVP|HVD|HVN|HVI|VBP|VAG|VAN|VB|VBN|VBD|VBP|VBI)]`

Mostly ME stuff. Non-ME stuff: a *got* passive, a typo, and *seemed...displeased*. Will check ME stuff more closely later, though it mostly seems like subjunctive past copulas used in passive constructions.

Ignoring VAN sisters yields just two other sentences, one a typo.
