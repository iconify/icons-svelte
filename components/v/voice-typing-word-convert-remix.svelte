<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu8d-fbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gu8d-fbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:voice-typing-word-convert-remix" {...props}></Icon>
