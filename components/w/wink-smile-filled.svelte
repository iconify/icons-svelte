<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxsj9xn3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxsj9xn3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wink-smile-filled" {...props}></Icon>
