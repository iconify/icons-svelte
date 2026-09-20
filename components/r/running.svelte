<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu2o_0bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zu2o_0bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:running" {...props}></Icon>
