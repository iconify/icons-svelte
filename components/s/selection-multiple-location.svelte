<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0-dt9s6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0-dt9s6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection-multiple-location" {...props}></Icon>
