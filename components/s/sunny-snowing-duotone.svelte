<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qczgm22wk.css';
import '../../css/k/k3_uumdyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qczgm22wk"/><path class="k3_uumdyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sunny-snowing-duotone" {...props}></Icon>
