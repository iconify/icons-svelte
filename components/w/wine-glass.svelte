<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbcehbbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbcehbbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:wine-glass" {...props}></Icon>
