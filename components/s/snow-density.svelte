<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k20av7rgb.css';
import '../../css/h/hzik1vb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k20av7rgb"/><path class="hzik1vb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:snow-density" {...props}></Icon>
