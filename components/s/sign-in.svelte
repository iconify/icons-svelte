<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zonh8mbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="zonh8mbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:sign-in" {...props}></Icon>
