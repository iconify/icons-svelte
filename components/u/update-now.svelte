<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfqul596w.css';
import '../../css/a/ao5bk4bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wfqul596w"/><path class="ao5bk4bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:update-now" {...props}></Icon>
