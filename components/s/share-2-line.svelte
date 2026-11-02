<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws4ge5kmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws4ge5kmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:share-2-line" {...props}></Icon>
