<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh3nt46sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mh3nt46sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:train" {...props}></Icon>
