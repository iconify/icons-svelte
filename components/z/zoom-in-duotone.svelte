<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ay5e68biv.css';
import '../../css/y/y0v0lz-zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ay5e68biv"/><path class="y0v0lz-zg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:zoom-in-duotone" {...props}></Icon>
