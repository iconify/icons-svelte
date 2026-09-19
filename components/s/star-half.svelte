<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e42tj16gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e42tj16gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:star-half" {...props}></Icon>
