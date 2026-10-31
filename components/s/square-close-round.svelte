<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zai59nb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zai59nb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-close-round" {...props}></Icon>
