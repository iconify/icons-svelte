<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq0ony_kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wq0ony_kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-progress" {...props}></Icon>
