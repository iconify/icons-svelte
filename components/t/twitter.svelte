<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs_17i3uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fs_17i3uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:twitter" {...props}></Icon>
