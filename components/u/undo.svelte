<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvh4r_b8g.css';
import '../../css/d/dt926jbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvh4r_b8g wm-k"/><path class="dt926jbqr wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:undo" {...props}></Icon>
