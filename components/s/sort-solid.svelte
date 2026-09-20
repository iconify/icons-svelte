<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/objzvbc8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="objzvbc8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sort-solid" {...props}></Icon>
