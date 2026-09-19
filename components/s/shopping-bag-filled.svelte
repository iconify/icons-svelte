<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np9t7bbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np9t7bbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shopping-bag-filled" {...props}></Icon>
