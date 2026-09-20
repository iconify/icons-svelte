<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5t501gxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5t501gxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:store-edit" {...props}></Icon>
