<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkr-217ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wkr-217ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:thermometer-solid" {...props}></Icon>
