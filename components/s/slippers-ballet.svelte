<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgf-7tbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgf-7tbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slippers-ballet" {...props}></Icon>
