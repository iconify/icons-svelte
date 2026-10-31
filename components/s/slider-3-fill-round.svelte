<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh_6htbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh_6htbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:slider-3-fill-round" {...props}></Icon>
