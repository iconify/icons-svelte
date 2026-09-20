<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bthvc4b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bthvc4b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:triangle" {...props}></Icon>
