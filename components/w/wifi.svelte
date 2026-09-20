<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwpti4c9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pwpti4c9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wifi" {...props}></Icon>
