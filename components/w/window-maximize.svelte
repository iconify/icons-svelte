<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huryb7cmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huryb7cmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:window-maximize" {...props}></Icon>
