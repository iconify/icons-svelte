<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsn881bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rsn881bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:thumbsup" {...props}></Icon>
