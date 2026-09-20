<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfd9-ubvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qfd9-ubvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spoon-and-chopsticks" {...props}></Icon>
