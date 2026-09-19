<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8mvcmb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":400,"height":512};
const content = `<path class="c8mvcmb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ttcn-3" {...props}></Icon>
