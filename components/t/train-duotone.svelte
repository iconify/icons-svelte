<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ce01a5bpd.css';
import '../../css/x/xn83ck27j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ce01a5bpd"/><path class="xn83ck27j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:train-duotone" {...props}></Icon>
