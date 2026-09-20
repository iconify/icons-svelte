<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5tdrabfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5tdrabfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:voice-scan-1-remix" {...props}></Icon>
