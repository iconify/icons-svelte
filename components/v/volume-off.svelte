<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udpa8y6px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udpa8y6px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:volume-off" {...props}></Icon>
