<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9gx3uspy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9gx3uspy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:traffic-lights-fill" {...props}></Icon>
