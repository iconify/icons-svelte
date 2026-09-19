<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7jnqub0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="c7jnqub0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:t-square" {...props}></Icon>
