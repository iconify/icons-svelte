<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg1z4-d7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg1z4-d7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shopping-basket-remove" {...props}></Icon>
