<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y90iic0su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y90iic0su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-check" {...props}></Icon>
