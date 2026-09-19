<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtu1g4rxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wtu1g4rxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:switch" {...props}></Icon>
