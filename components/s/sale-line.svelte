<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt1wq7lox.css';
import '../../css/k/kabj7mbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt1wq7lox"/><path class="kabj7mbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sale-line" {...props}></Icon>
