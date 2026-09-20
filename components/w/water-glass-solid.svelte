<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl1cs6bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zl1cs6bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:water-glass-solid" {...props}></Icon>
