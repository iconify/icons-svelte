<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz8-9gwgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cz8-9gwgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sparkle-alt-fill-20" {...props}></Icon>
