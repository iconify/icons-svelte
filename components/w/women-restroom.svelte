<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5jnj4b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5jnj4b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:women-restroom" {...props}></Icon>
