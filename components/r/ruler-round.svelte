<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iywt5db8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iywt5db8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ruler-round" {...props}></Icon>
