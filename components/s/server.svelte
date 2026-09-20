<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw5goxb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="jw5goxb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:server" {...props}></Icon>
