<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1cbfwy3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z1cbfwy3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:thumbs-up-sharp" {...props}></Icon>
