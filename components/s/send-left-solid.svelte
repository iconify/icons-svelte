<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg0mhxhmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kg0mhxhmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-left-solid" {...props}></Icon>
