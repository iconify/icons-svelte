<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geki3y6gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geki3y6gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevron-right-sharp-fill" {...props}></Icon>
