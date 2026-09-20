<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f08ikcb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f08ikcb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:strikethrough" {...props}></Icon>
