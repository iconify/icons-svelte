<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uou8spbqk.css';
import '../../css/y/y306aceyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uou8spbqk"/><path class="y306aceyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:webcam" {...props}></Icon>
