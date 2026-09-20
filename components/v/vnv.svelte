<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_lt3l0cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e_lt3l0cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vnv" {...props}></Icon>
