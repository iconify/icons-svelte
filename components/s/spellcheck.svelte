<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcwgvlb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="kcwgvlb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spellcheck" {...props}></Icon>
