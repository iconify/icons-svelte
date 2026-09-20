<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl8zs6bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl8zs6bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:spinrilla-logo" {...props}></Icon>
