<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asz6tco0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asz6tco0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:star-off" {...props}></Icon>
