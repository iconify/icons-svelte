<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkophlb7r.css';
import '../../css/x/xiggllbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xkophlb7r"/><path class="xiggllbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:street-light-20-bold" {...props}></Icon>
