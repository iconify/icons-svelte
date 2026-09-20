<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhvtq4btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhvtq4btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:screencastify" {...props}></Icon>
