<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc6m-t-sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc6m-t-sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:twinmotion" {...props}></Icon>
