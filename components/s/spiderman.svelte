<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxh8cdbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":835,"height":1024};
const content = `<path class="fxh8cdbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:spiderman" {...props}></Icon>
