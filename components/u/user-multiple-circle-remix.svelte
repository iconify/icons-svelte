<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkzodjq2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pkzodjq2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:user-multiple-circle-remix" {...props}></Icon>
