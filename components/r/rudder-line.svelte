<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvjbrz5oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvjbrz5oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rudder-line" {...props}></Icon>
