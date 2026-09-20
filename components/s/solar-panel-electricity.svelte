<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epubeu-jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epubeu-jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:solar-panel-electricity" {...props}></Icon>
