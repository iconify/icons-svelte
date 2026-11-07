<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/acmhcgbix.css';
import '../../css/r/rf3amc9mv.css';
import '../../css/t/t2jvb6bpe.css';
import '../../css/i/ic59sq0-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="acmhcgbix"/><path class="rf3amc9mv"/><path class="t2jvb6bpe"/><path class="ic59sq0-o"/><path class="t2jvb6bpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-broken" {...props}></Icon>
