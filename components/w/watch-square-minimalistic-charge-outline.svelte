<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3glk0b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f3glk0b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-square-minimalistic-charge-outline" {...props}></Icon>
