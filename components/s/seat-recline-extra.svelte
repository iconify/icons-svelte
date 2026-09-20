<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kega9ac9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kega9ac9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-recline-extra" {...props}></Icon>
