<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wllrp9urp.css';
import '../../css/c/czs93-zxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wllrp9urp"/><path class="czs93-zxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:statue-of-liberty-line" {...props}></Icon>
