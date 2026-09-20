<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5rgnrbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5rgnrbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:warm-up-2-line" {...props}></Icon>
