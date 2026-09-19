<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chkf3ns7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="chkf3ns7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:stop-circle" {...props}></Icon>
