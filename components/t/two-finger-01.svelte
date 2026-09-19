<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjw82aboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjw82aboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:two-finger-01" {...props}></Icon>
