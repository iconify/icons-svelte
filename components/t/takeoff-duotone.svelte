<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g42mrps4n.css';
import '../../css/y/yb901tbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g42mrps4n"/><path class="yb901tbth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:takeoff-duotone" {...props}></Icon>
