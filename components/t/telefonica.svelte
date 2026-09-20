<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iej9w3psn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iej9w3psn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:telefonica" {...props}></Icon>
