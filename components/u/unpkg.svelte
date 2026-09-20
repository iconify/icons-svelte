<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo4a6jivs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo4a6jivs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:unpkg" {...props}></Icon>
