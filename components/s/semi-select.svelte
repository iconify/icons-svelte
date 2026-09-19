<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxrugac4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yxrugac4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:semi-select" {...props}></Icon>
