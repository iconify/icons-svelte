<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8bulmb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8bulmb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-youtube" {...props}></Icon>
