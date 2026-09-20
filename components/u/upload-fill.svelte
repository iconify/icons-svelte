<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs6_p0ttt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs6_p0ttt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:upload-fill" {...props}></Icon>
