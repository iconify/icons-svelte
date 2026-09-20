<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq0-shbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="rq0-shbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:x" {...props}></Icon>
