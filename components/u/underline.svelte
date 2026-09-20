<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3_en-bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="z3_en-bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:underline" {...props}></Icon>
