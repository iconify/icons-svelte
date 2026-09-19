<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajbve8uyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ajbve8uyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-letterboxd" {...props}></Icon>
