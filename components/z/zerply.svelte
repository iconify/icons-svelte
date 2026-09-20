<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc94w3amr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc94w3amr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zerply" {...props}></Icon>
