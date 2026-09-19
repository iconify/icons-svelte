<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxchkfu3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gxchkfu3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:side-panel-open-filled" {...props}></Icon>
