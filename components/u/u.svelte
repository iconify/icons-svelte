<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k82mb-blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="k82mb-blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:u" {...props}></Icon>
