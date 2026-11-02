<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3ch4dbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3ch4dbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:virgo-line" {...props}></Icon>
