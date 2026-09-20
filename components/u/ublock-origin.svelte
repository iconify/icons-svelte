<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v08tzf_qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v08tzf_qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ublock-origin" {...props}></Icon>
