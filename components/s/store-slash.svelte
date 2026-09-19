<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0b7g1b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d0b7g1b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:store-slash" {...props}></Icon>
