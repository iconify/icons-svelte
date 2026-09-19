<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht8bghaxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ht8bghaxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:uneditable-solid-12" {...props}></Icon>
