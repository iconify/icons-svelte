<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9b_hg85a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9b_hg85a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:store-3-fill" {...props}></Icon>
