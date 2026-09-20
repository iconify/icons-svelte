<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0pww9bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t0pww9bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:six-pips" {...props}></Icon>
