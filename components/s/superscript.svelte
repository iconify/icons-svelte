<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2fuo2bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l2fuo2bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:superscript" {...props}></Icon>
