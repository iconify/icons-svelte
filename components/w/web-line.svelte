<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwfm1uuyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwfm1uuyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:web-line" {...props}></Icon>
