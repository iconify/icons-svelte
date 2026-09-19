<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqa2xhb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vqa2xhb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:sound-off-solid" {...props}></Icon>
