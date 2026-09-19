<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3p6v5b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f3p6v5b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-stroke-16" {...props}></Icon>
