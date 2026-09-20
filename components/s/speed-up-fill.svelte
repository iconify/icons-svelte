<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se7a8gbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se7a8gbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speed-up-fill" {...props}></Icon>
