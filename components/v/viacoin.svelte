<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zda3z-uqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="zda3z-uqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:viacoin" {...props}></Icon>
