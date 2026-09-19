<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kub96ib8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="kub96ib8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tray-speech-bubble-26" {...props}></Icon>
