<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/funxt_b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="funxt_b8b thealgorithms-plain-#000000"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:thealgorithms" {...props}></Icon>
