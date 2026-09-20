<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwknlm9zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwknlm9zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:xbox-controller-battery-full" {...props}></Icon>
