<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmrrr4bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pmrrr4bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sparkle-stroke-16" {...props}></Icon>
