<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g05i0xqhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g05i0xqhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:subtitle-fill" {...props}></Icon>
