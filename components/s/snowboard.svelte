<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-i8x-tan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v-i8x-tan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:snowboard" {...props}></Icon>
