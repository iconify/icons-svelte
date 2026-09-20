<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sybtc-v9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sybtc-v9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:synchronize-warning-solid" {...props}></Icon>
