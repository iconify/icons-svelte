<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfwfh6omr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfwfh6omr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:spotlight" {...props}></Icon>
