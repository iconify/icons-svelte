<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2a39z7-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2a39z7-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevron-up-sharp-fill" {...props}></Icon>
