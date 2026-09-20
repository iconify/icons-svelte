<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlx16osnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlx16osnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:server-fault" {...props}></Icon>
