<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llnp5hb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="llnp5hb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:z" {...props}></Icon>
