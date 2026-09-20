<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pso7n1cmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pso7n1cmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rust-outline" {...props}></Icon>
