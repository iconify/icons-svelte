<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/likc0vc3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="likc0vc3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:textbox-ai-fill" {...props}></Icon>
