<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufkxafb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ufkxafb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-down-solid" {...props}></Icon>
