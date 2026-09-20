<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbjbhable.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbjbhable"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:starz" {...props}></Icon>
