<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu55eybqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu55eybqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:slide" {...props}></Icon>
