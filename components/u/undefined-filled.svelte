<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1qo09e8y.css';
import '../../css/x/xpcfinb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c1qo09e8y"/><path class="xpcfinb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:undefined-filled" {...props}></Icon>
