<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eugvkacpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eugvkacpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:t-shirt-air-line" {...props}></Icon>
