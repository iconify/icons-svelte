<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh4r42bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh4r42bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:step-forward" {...props}></Icon>
