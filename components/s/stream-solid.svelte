<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd7pgj9zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jd7pgj9zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stream-solid" {...props}></Icon>
