<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsqfb5o5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsqfb5o5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:slash-sharp-duotone" {...props}></Icon>
