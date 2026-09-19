<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo0ac2boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jo0ac2boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:tree" {...props}></Icon>
