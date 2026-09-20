<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tekvm-b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tekvm-b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:unlock" {...props}></Icon>
