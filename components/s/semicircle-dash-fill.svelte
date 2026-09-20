<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0nkrereh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0nkrereh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:semicircle-dash-fill" {...props}></Icon>
