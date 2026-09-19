<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-0co0btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-0co0btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:thermometer-filled" {...props}></Icon>
