<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhmr2ua0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhmr2ua0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ship-steering-wheel" {...props}></Icon>
