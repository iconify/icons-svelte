<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owh6n4siz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="owh6n4siz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:watch" {...props}></Icon>
