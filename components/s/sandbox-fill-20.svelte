<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig-lqcc0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ig-lqcc0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sandbox-fill-20" {...props}></Icon>
