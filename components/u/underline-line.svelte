<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh36tcbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh36tcbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:underline-line" {...props}></Icon>
