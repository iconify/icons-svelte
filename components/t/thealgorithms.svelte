<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-62rbbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q-62rbbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:thealgorithms" {...props}></Icon>
