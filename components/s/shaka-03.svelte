<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbfxk0b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbfxk0b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shaka-03" {...props}></Icon>
