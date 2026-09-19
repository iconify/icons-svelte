<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u89uutp6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u89uutp6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-search" {...props}></Icon>
