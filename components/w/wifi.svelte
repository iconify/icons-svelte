<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsh3n7vpt.css';
import '../../css/n/npoomsb7x.css';
import '../../css/s/sg68hbv5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":34,"height":24};
const content = `<path class="nsh3n7vpt"/><path class="npoomsb7x"/><path class="sg68hbv5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:wifi" {...props}></Icon>
