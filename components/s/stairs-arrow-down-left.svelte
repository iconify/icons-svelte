<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxi5_9bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxi5_9bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:stairs-arrow-down-left" {...props}></Icon>
