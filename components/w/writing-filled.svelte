<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jusq19xev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jusq19xev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:writing-filled" {...props}></Icon>
