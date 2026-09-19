<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz-hmbbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jz-hmbbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tilde" {...props}></Icon>
