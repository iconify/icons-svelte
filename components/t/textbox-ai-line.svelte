<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zao_biosz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zao_biosz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:textbox-ai-line" {...props}></Icon>
