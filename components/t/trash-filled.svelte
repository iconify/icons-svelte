<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0iih6b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0iih6b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:trash-filled" {...props}></Icon>
