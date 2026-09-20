<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6lq83bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u6lq83bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:view-columns" {...props}></Icon>
