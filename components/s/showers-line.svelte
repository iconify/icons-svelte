<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-om3ebjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-om3ebjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:showers-line" {...props}></Icon>
