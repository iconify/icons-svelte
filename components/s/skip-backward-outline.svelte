<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq97zwull.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq97zwull"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:skip-backward-outline" {...props}></Icon>
