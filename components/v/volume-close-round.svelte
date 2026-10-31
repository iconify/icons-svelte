<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw02nnoal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw02nnoal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-close-round" {...props}></Icon>
