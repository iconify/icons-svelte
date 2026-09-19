<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y10l5hgkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y10l5hgkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-square-thin" {...props}></Icon>
