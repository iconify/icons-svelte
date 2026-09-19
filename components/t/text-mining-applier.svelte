<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxlwz1bsp.css';
import '../../css/u/ua6u3wino.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zxlwz1bsp"/><path class="ua6u3wino"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-mining-applier" {...props}></Icon>
