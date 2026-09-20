<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbbh5bc4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbbh5bc4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:youtube-fill" {...props}></Icon>
