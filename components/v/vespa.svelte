<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i83wwl13m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i83wwl13m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vespa" {...props}></Icon>
