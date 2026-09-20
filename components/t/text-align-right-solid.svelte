<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m96ctz9ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m96ctz9ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:text-align-right-solid" {...props}></Icon>
