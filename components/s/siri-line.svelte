<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh7b57y_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh7b57y_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:siri-line" {...props}></Icon>
