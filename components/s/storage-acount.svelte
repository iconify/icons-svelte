<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uub89fbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uub89fbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:storage-acount" {...props}></Icon>
