<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t440isbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t440isbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:webcam-check" {...props}></Icon>
