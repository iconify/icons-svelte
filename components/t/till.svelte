<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf3ugybwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf3ugybwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:till" {...props}></Icon>
