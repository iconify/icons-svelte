<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyampacxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyampacxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tindie" {...props}></Icon>
