<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adj7ecb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adj7ecb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-10" {...props}></Icon>
