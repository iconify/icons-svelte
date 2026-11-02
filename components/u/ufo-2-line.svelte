<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjf-5bbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjf-5bbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ufo-2-line" {...props}></Icon>
