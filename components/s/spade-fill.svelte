<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g63kmynmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g63kmynmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spade-fill" {...props}></Icon>
