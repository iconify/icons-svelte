<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qju7tw8fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qju7tw8fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-direction-left-fill" {...props}></Icon>
