<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3fcxib2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v3fcxib2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:wiiu" {...props}></Icon>
