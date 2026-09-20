<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1e431b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z1e431b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tag-alt-remix" {...props}></Icon>
