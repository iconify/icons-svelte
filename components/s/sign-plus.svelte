<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr941acet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr941acet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus" {...props}></Icon>
