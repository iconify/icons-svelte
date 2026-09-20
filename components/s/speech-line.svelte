<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tecw7fbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tecw7fbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:speech-line" {...props}></Icon>
