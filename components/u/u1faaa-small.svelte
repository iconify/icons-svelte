<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bva-u7fvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bva-u7fvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:u1faaa-small" {...props}></Icon>
