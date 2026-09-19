<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-29jsqsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-29jsqsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ruble-filled" {...props}></Icon>
