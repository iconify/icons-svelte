<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sah62hazp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sah62hazp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-multiple" {...props}></Icon>
