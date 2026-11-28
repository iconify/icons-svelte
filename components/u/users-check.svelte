<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lru3qwfcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lru3qwfcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:users-check" {...props}></Icon>
