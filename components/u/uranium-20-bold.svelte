<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv5gi5b9f.css';
import '../../css/l/l624pqxrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zv5gi5b9f"/><path class="l624pqxrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:uranium-20-bold" {...props}></Icon>
