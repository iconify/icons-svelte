<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iemz6buzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iemz6buzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:shopping-basket-2" {...props}></Icon>
