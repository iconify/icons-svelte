<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eef4yzd1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eef4yzd1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:train-speed" {...props}></Icon>
