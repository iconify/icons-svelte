<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8o6k5bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8o6k5bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wifi-medium-fill-round" {...props}></Icon>
