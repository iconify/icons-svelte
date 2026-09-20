<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knhzlwgrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knhzlwgrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shield-star-line" {...props}></Icon>
