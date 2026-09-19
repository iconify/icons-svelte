<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwsr9cbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="uwsr9cbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:twitter-alt" {...props}></Icon>
