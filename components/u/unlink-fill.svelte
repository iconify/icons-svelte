<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhgr8wb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhgr8wb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:unlink-fill" {...props}></Icon>
