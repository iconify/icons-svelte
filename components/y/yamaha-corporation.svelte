<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-msx3-8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-msx3-8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yamaha-corporation" {...props}></Icon>
