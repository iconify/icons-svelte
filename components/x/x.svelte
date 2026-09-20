<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtld2xbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtld2xbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x" {...props}></Icon>
