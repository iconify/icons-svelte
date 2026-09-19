<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0ulpub6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="v0ulpub6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:window-restore" {...props}></Icon>
