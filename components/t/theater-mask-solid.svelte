<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijab_1a-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ijab_1a-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:theater-mask-solid" {...props}></Icon>
