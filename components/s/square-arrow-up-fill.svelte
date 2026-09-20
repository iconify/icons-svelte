<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vidp6ebdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vidp6ebdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-up-fill" {...props}></Icon>
