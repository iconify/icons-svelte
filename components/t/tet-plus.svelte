<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzbz9xb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzbz9xb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tet-plus" {...props}></Icon>
