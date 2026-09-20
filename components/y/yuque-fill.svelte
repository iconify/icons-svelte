<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra53sfbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra53sfbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:yuque-fill" {...props}></Icon>
