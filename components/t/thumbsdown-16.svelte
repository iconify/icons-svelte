<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8toi509j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r8toi509j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:thumbsdown-16" {...props}></Icon>
