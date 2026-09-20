<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngt0lm-8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ngt0lm-8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:uber" {...props}></Icon>
