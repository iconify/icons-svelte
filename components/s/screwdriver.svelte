<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go9v-oadc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go9v-oadc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:screwdriver" {...props}></Icon>
