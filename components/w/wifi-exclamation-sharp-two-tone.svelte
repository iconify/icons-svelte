<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/akajwubis.css';
import '../../css/y/yepmwko9k.css';
import '../../css/k/ksan_mr5a.css';
import '../../css/n/n2jrplbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="akajwubis"/><path class="yepmwko9k"/><path class="ksan_mr5a"/><path class="n2jrplbtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wifi-exclamation-sharp-two-tone" {...props}></Icon>
