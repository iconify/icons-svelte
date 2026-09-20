<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eemv9t5oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eemv9t5oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:window-minimize" {...props}></Icon>
