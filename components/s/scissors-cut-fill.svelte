<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aub60qb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aub60qb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scissors-cut-fill" {...props}></Icon>
