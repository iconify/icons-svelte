<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh36b_exl.css';
import '../../css/t/t2wztiban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bh36b_exl"/><path class="t2wztiban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:worship-muslim" {...props}></Icon>
