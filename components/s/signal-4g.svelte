<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlrbi4nyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlrbi4nyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signal-4g" {...props}></Icon>
