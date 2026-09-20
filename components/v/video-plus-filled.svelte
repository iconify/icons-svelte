<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a36u_tb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a36u_tb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:video-plus-filled" {...props}></Icon>
