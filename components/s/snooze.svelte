<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhpymzg_r.css';
import '../../css/c/ctg85nb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jhpymzg_r"/><path class="ctg85nb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:snooze" {...props}></Icon>
