<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soy094b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="soy094b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xmo" {...props}></Icon>
