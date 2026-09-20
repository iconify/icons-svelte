<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqh0-kb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqh0-kb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shield-line" {...props}></Icon>
