<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y42ejk31t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y42ejk31t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-minus-round" {...props}></Icon>
