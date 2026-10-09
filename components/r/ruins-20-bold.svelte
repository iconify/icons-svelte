<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfoxxnbix.css';
import '../../css/y/yhs2jn2-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yfoxxnbix"/><path class="yhs2jn2-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ruins-20-bold" {...props}></Icon>
