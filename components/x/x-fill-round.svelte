<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjdw1nwta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjdw1nwta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:x-fill-round" {...props}></Icon>
