<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p68jygbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p68jygbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:typhoon-line" {...props}></Icon>
