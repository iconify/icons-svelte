<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqag-kbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="jqag-kbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:vimeo" {...props}></Icon>
