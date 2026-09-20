<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipqw2w6vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ipqw2w6vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:typescript-solid" {...props}></Icon>
