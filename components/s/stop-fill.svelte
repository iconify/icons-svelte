<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c911d0bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c911d0bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stop-fill" {...props}></Icon>
