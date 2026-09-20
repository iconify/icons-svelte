<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eudn5vbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="eudn5vbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-right-solid" {...props}></Icon>
