<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k87mgcena.css';
import '../../css/h/hwg0k-kmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k87mgcena"/><path class="hwg0k-kmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tag-export" {...props}></Icon>
