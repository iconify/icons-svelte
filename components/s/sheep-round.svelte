<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flk5pbbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flk5pbbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sheep-round" {...props}></Icon>
