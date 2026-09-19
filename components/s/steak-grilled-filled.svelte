<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sulgjdb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sulgjdb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:steak-grilled-filled" {...props}></Icon>
