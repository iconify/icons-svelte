<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x254e0blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x254e0blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:skip-forward" {...props}></Icon>
