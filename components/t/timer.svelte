<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exqw53b-w.css';
import '../../css/v/v2qi5lg1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="exqw53b-w"/><path class="v2qi5lg1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:timer" {...props}></Icon>
