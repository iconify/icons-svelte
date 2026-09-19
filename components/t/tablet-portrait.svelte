<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/temo6clri.css';
import '../../css/j/j052408uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="temo6clri"/><path class="j052408uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:tablet-portrait" {...props}></Icon>
