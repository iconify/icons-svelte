<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xym376n8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xym376n8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:send-alt-2-filled" {...props}></Icon>
