<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo1wiob4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":472};
const content = `<path class="jo1wiob4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sound" {...props}></Icon>
