<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-4or8fvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-4or8fvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:surround-sound-2-1" {...props}></Icon>
