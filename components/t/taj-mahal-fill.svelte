<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0m489b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m0m489b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taj-mahal-fill" {...props}></Icon>
