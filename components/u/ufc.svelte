<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbzz0_v3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbzz0_v3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ufc" {...props}></Icon>
