<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3rsk1bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3rsk1bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:shopping-basket" {...props}></Icon>
