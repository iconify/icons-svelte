<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q34h2vb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q34h2vb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:whiteboard-alt-filled" {...props}></Icon>
