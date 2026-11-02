<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2qfondcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2qfondcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:warm-up-3-fill" {...props}></Icon>
