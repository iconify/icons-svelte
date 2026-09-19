<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awms53bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="awms53bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sigma" {...props}></Icon>
