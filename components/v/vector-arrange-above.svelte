<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf1qn4z0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf1qn4z0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-arrange-above" {...props}></Icon>
