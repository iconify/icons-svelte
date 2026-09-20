<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqnd2uppl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqnd2uppl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sega" {...props}></Icon>
