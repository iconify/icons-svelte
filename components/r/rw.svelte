<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp4mm0b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dp4mm0b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:rw" {...props}></Icon>
