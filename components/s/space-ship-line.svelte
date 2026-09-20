<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flgm55cub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flgm55cub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:space-ship-line" {...props}></Icon>
