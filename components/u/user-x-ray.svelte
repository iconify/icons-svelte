<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-wun9brn.css';
import '../../css/l/libay-4ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c-wun9brn"/><path class="libay-4ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-x-ray" {...props}></Icon>
