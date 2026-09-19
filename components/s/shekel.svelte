<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcs7_bcpt.css';
import '../../css/k/kvsed47hf.css';
import '../../css/u/uqfhxrrcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bcs7_bcpt"/><path class="kvsed47hf"/><path class="uqfhxrrcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:shekel" {...props}></Icon>
