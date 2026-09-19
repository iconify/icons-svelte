<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuzd39s8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wuzd39s8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:viadeo-square" {...props}></Icon>
