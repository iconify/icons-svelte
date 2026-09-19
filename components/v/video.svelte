<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0v9pbb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t0v9pbb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:video" {...props}></Icon>
