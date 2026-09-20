<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfipvoh5c.css';
import '../../css/p/pmw0v_bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfipvoh5c"/><path class="pmw0v_bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-shine-big-eyes" {...props}></Icon>
