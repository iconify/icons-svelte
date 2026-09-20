<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzmes-lrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vzmes-lrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:warning-octagon-remix" {...props}></Icon>
