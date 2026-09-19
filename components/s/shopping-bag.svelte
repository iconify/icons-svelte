<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0827ujmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0827ujmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:shopping-bag" {...props}></Icon>
