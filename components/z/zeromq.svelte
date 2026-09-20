<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9dtcsm4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9dtcsm4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zeromq" {...props}></Icon>
