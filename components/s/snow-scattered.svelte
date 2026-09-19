<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys42lxb9r.css';
import '../../css/k/ky_i-dbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ys42lxb9r"/><path class="ky_i-dbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:snow-scattered" {...props}></Icon>
