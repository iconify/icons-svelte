<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujzfkkbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujzfkkbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shopping-basket-filled" {...props}></Icon>
