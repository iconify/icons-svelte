<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxtz4dbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxtz4dbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:seedling-fill" {...props}></Icon>
