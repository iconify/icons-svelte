<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcqr5ubrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xcqr5ubrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:water-sun" {...props}></Icon>
