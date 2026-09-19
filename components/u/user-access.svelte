<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw06c_omj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yw06c_omj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-access" {...props}></Icon>
