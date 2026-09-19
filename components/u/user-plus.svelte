<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he1e84igr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="he1e84igr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:user-plus" {...props}></Icon>
