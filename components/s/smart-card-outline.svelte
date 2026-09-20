<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4hm2ymux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4hm2ymux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smart-card-outline" {...props}></Icon>
