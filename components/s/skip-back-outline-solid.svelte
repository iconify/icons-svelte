<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogsihlbkj.css';
import '../../css/s/svdy80z7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ogsihlbkj"/><path class="svdy80z7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-back-outline-solid" {...props}></Icon>
