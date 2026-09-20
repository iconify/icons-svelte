<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kgmgfacjn.css';
import '../../css/i/ip95smfdk.css';
import '../../css/h/h02m9fm5b.css';
import '../../css/s/szhd4pbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kgmgfacjn"/><path class="ip95smfdk"/><path class="h02m9fm5b"/><path class="szhd4pbou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tower-clock" {...props}></Icon>
