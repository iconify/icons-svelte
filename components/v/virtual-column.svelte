<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh21c1arq.css';
import '../../css/g/gin_3l1fi.css';
import '../../css/y/yzfdw0bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zh21c1arq"/><path class="gin_3l1fi"/><path class="yzfdw0bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:virtual-column" {...props}></Icon>
