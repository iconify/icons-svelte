<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0-hm3t7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0-hm3t7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:volume-mute" {...props}></Icon>
