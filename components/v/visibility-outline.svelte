<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co9xgs76y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co9xgs76y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:visibility-outline" {...props}></Icon>
