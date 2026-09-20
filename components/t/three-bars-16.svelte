<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amy3jaclb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="amy3jaclb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:three-bars-16" {...props}></Icon>
