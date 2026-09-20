<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgpz1hb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgpz1hb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transmission-outline" {...props}></Icon>
