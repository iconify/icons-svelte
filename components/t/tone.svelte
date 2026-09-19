<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th9jinbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th9jinbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:tone" {...props}></Icon>
