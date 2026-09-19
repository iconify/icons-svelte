<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyt5j2bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tyt5j2bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:schematics" {...props}></Icon>
