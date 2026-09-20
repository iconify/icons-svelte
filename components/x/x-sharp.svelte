<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfyfzv5at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfyfzv5at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:x-sharp" {...props}></Icon>
