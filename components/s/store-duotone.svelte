<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r1gp5-u1c.css';
import '../../css/m/myw_a-bni.css';
import '../../css/k/kb9eddb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r1gp5-u1c"/><path class="myw_a-bni"/><path class="kb9eddb8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:store-duotone" {...props}></Icon>
