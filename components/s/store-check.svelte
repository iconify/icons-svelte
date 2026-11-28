<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap4_hdctl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ap4_hdctl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:store-check" {...props}></Icon>
