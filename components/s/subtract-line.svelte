<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvonjr_9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvonjr_9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:subtract-line" {...props}></Icon>
