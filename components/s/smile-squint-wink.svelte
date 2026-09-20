<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcb5u9bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcb5u9bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:smile-squint-wink" {...props}></Icon>
