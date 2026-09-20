<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vao15ubdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vao15ubdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:sign-outline" {...props}></Icon>
