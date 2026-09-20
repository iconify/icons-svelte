<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmc1oxfsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmc1oxfsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:video-minus-fill" {...props}></Icon>
