<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbdvy7bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hbdvy7bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:target-3-solid" {...props}></Icon>
