<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_g18uqvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_g18uqvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sailboat-line" {...props}></Icon>
