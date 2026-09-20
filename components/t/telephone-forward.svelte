<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fos3e4dkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fos3e4dkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-forward" {...props}></Icon>
