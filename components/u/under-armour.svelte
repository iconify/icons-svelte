<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nch7ptbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nch7ptbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:under-armour" {...props}></Icon>
