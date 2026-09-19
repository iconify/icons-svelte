<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8pdp68ro.css';
import '../../css/t/t-wcwabfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w8pdp68ro"/><path class="t-wcwabfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scalpel-lasso" {...props}></Icon>
