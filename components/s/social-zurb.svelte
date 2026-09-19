<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abj0z4bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="abj0z4bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-zurb" {...props}></Icon>
