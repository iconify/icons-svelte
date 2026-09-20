<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5p3c1b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a5p3c1b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:shield-alt-solid" {...props}></Icon>
