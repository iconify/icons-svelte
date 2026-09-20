<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_-lpjk0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_-lpjk0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stethoscope-fill" {...props}></Icon>
