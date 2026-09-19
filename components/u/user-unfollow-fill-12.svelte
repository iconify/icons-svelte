<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m23wrpw-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m23wrpw-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-unfollow-fill-12" {...props}></Icon>
