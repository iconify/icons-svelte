<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohu3o4set.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohu3o4set"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trainerroad" {...props}></Icon>
