<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weq3sf4aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weq3sf4aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-3-fill" {...props}></Icon>
