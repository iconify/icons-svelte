<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8ikm3bfk.css';
import '../../css/p/p39-tabus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8ikm3bfk"/><path class="p39-tabus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wrist-watch-round-filled" {...props}></Icon>
