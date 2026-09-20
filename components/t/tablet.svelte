<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqc9t5egf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zqc9t5egf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:tablet" {...props}></Icon>
