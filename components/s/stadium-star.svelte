<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt0i_6v5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt0i_6v5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:stadium-star" {...props}></Icon>
