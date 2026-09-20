<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmdqm12tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmdqm12tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:zoom-in" {...props}></Icon>
