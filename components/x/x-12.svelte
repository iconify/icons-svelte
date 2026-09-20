<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6fvybcit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j6fvybcit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:x-12" {...props}></Icon>
