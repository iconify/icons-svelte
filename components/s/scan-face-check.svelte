<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbkayy0nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbkayy0nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:scan-face-check" {...props}></Icon>
