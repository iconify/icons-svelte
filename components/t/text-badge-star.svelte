<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmjbcrbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zmjbcrbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-badge-star" {...props}></Icon>
