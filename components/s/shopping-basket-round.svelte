<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7d4biy9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7d4biy9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-basket-round" {...props}></Icon>
