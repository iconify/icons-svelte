<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp8rk1bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yp8rk1bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:windmill-solid" {...props}></Icon>
