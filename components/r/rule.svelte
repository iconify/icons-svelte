<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg4u3kb1v.css';
import '../../css/e/ey3vbs2kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bg4u3kb1v"/><path class="ey3vbs2kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:rule" {...props}></Icon>
