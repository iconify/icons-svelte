<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fits8bbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fits8bbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:skull-2" {...props}></Icon>
