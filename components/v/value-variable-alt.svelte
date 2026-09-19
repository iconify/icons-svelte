<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo8vbxb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fo8vbxb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:value-variable-alt" {...props}></Icon>
