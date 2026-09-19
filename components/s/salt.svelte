<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnek59blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fnek59blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:salt" {...props}></Icon>
