<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hieyli1np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hieyli1np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-size-decrease-duotone-round" {...props}></Icon>
