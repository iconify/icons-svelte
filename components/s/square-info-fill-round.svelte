<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9iix5bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9iix5bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-info-fill-round" {...props}></Icon>
