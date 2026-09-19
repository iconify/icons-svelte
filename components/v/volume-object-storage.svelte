<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeqn9cblo.css';
import '../../css/r/rauwxcb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aeqn9cblo"/><path class="rauwxcb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-object-storage" {...props}></Icon>
