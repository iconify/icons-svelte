<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8n8jh6bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8n8jh6bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:speech-bubble-inactive" {...props}></Icon>
