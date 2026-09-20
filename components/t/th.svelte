<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufay8wlzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufay8wlzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:th" {...props}></Icon>
