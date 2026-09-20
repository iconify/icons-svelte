<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e84xfbb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e84xfbb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:truck-solid" {...props}></Icon>
