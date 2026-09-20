<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_i-061gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y_i-061gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:undo-alt-solid" {...props}></Icon>
