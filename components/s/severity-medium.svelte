<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydsmyebdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ydsmyebdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:severity-medium" {...props}></Icon>
