<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcndpib8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcndpib8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-alert" {...props}></Icon>
