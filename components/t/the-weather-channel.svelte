<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyf-acb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyf-acb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:the-weather-channel" {...props}></Icon>
