<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cporbno1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cporbno1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:z" {...props}></Icon>
