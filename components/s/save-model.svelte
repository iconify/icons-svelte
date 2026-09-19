<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl4tf0b_w.css';
import '../../css/z/z916qcbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tl4tf0b_w"/><path class="z916qcbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:save-model" {...props}></Icon>
