<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc4ux5b6q.css';
import '../../css/r/ry9w0vp7y.css';
import '../../css/f/fm0qv_wws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mc4ux5b6q"/><path class="ry9w0vp7y"/><path class="fm0qv_wws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:target-16" {...props}></Icon>
