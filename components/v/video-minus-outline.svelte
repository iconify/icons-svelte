<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8eain-5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8eain-5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-minus-outline" {...props}></Icon>
