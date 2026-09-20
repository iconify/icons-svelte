<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whqk7pb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whqk7pb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:transmission-square-outline" {...props}></Icon>
