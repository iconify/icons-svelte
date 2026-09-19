<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-89v3b5b.css';
import '../../css/f/fjhdmsv1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k-89v3b5b"/><path class="fjhdmsv1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tag-none" {...props}></Icon>
