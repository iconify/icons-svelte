<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klz_rcchj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klz_rcchj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:sort-za" {...props}></Icon>
