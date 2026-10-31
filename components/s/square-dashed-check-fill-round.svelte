<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk85qacez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk85qacez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-check-fill-round" {...props}></Icon>
