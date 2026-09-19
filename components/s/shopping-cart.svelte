<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c04q_6b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c04q_6b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:shopping-cart" {...props}></Icon>
