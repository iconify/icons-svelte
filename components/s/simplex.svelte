<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rko2gt8go.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rko2gt8go"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:simplex" {...props}></Icon>
