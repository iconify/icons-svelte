<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnrbw7e8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnrbw7e8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:shopping-cart" {...props}></Icon>
