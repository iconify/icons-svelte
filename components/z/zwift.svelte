<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc6m4nbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc6m4nbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zwift" {...props}></Icon>
