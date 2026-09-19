<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1fggzqzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h1fggzqzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:tv" {...props}></Icon>
