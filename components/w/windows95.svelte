<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9rmiibdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9rmiibdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:windows95" {...props}></Icon>
