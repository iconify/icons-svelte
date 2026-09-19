<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1u1swbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="t1u1swbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:underline" {...props}></Icon>
