<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/najqe30yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="najqe30yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:star-half-outline" {...props}></Icon>
