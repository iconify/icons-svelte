<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmhddevn.css';
import '../../css/b/b-_0m7wwh.css';
import '../../css/u/ueg81y61d.css';
import '../../css/y/yi1xvlb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="lgmhddevn"/><path class="b-_0m7wwh"/><path class="ueg81y61d"/><path class="yi1xvlb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-view" {...props}></Icon>
