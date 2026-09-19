<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-i6ib76y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t-i6ib76y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-right-stroke-12" {...props}></Icon>
