<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxt_agb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxt_agb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:search" {...props}></Icon>
