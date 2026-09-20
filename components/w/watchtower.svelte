<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdfe7tbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdfe7tbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:watchtower" {...props}></Icon>
