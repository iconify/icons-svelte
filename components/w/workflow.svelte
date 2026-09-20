<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svxl2rzhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svxl2rzhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:workflow" {...props}></Icon>
