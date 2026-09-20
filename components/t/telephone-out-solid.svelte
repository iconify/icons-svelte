<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-2vgez0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-2vgez0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:telephone-out-solid" {...props}></Icon>
