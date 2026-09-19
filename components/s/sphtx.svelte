<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwwtadc2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hwwtadc2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sphtx" {...props}></Icon>
