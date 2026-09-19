<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov4uribag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ov4uribag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-sponsor" {...props}></Icon>
