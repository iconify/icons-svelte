<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj80a9b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj80a9b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scale-round" {...props}></Icon>
