<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgn0bs1rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lgn0bs1rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:taxi" {...props}></Icon>
