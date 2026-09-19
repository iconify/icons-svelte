<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixswl67rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ixswl67rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sina-weibo" {...props}></Icon>
