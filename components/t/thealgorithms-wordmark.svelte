<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjaj40bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kjaj40bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:thealgorithms-wordmark" {...props}></Icon>
