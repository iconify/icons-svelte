<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egmxbdbsh.css';
import '../../css/u/ur58omuhl.css';
import '../../css/x/xwdhawfba.css';
import '../../css/h/hayl1lfmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="egmxbdbsh"/><path class="ur58omuhl"/><path class="xwdhawfba"/><path class="hayl1lfmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-plus-20-bold" {...props}></Icon>
