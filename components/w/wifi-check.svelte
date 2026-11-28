<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgpn75uou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgpn75uou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wifi-check" {...props}></Icon>
