<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd37n7bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":416};
const content = `<path class="kd37n7bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:spellcheck" {...props}></Icon>
