<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x31obxwti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x31obxwti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thumbs-down" {...props}></Icon>
