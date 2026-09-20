<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km7fumb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km7fumb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spinner-3" {...props}></Icon>
