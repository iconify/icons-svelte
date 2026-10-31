<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjsde67-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjsde67-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:strikethrough-fill-round" {...props}></Icon>
