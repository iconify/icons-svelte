<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_kcb60rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i_kcb60rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:watch-circle-charging-solid" {...props}></Icon>
