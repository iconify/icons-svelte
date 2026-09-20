<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-vrwtbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-vrwtbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:star-fill" {...props}></Icon>
