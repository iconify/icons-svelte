<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj94jcb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xj94jcb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tools-alt" {...props}></Icon>
