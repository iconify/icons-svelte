<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfl-uc04m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lfl-uc04m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scooter" {...props}></Icon>
