<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/acmhcgbix.css';
import '../../css/p/py4d89c_p.css';
import '../../css/i/i2dleueig.css';
import '../../css/b/byf-qcfwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="acmhcgbix"/><path class="py4d89c_p"/><path class="i2dleueig"/><path class="byf-qcfwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-line-duotone" {...props}></Icon>
