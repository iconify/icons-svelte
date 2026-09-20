<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvn40n5nl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvn40n5nl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:xiaomi-mimo" {...props}></Icon>
