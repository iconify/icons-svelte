<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w42mnbcwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w42mnbcwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-size-increase-fill-round" {...props}></Icon>
