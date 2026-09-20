<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-g8xacav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-g8xacav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:triangle-up-16" {...props}></Icon>
