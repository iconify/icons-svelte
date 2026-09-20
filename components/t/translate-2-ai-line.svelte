<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6iwfab2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6iwfab2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:translate-2-ai-line" {...props}></Icon>
