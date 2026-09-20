<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfc1qmbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wfc1qmbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:user-identifier-card-remix" {...props}></Icon>
