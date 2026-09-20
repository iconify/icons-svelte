<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6w0w00-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6w0w00-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:visa-logo" {...props}></Icon>
