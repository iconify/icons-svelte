<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va9ht3buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va9ht3buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wave-square" {...props}></Icon>
