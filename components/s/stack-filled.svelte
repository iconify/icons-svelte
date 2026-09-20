<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zge4ebizx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zge4ebizx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stack-filled" {...props}></Icon>
