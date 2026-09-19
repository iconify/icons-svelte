<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkukszr9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkukszr9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sainsburys" {...props}></Icon>
