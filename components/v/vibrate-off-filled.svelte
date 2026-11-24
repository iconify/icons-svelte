<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/higjms7is.css';
import '../../css/f/frhkzlbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="higjms7is"/><path class="frhkzlbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:vibrate-off-filled" {...props}></Icon>
