<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er_fwrbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er_fwrbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sort-alphabet-desc" {...props}></Icon>
