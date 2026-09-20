<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frfs2zneh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frfs2zneh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shield-flash-fill" {...props}></Icon>
