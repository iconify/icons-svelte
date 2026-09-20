<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt6k55bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zt6k55bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:snapchat" {...props}></Icon>
