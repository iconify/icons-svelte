<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a89tfcbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a89tfcbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:tune" {...props}></Icon>
