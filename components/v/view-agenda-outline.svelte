<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a851iwg5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a851iwg5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-agenda-outline" {...props}></Icon>
