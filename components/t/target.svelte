<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss89lq90u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ss89lq90u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:target" {...props}></Icon>
