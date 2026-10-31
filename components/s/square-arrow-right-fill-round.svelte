<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egjrucbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egjrucbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-right-fill-round" {...props}></Icon>
