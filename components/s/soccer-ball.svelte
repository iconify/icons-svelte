<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7h7oigqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7h7oigqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:soccer-ball" {...props}></Icon>
