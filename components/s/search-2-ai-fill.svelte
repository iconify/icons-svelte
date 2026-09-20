<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpmobdbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpmobdbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-2-ai-fill" {...props}></Icon>
