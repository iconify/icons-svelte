<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb28gsi8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xb28gsi8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:straight-cap-remix" {...props}></Icon>
