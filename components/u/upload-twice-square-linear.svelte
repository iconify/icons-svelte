<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wi3cvkb9x.css';
import '../../css/b/b__-pabng.css';
import '../../css/i/ieyk-1btb.css';
import '../../css/x/xvjk-cbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wi3cvkb9x"/><path class="b__-pabng"/><path class="ieyk-1btb"/><path class="xvjk-cbox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-twice-square-linear" {...props}></Icon>
