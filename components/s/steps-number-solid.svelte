<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr8rlhbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr8rlhbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:steps-number-solid" {...props}></Icon>
