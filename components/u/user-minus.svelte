<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_-xp_znr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_-xp_znr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-minus" {...props}></Icon>
