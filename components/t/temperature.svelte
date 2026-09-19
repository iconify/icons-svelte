<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-f499btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b-f499btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:temperature" {...props}></Icon>
