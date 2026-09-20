<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8k4hcbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8k4hcbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:snapchat" {...props}></Icon>
