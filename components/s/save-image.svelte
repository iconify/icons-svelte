<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnlnjbcmb.css';
import '../../css/p/pt2uzac8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mnlnjbcmb"/><path class="pt2uzac8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:save-image" {...props}></Icon>
