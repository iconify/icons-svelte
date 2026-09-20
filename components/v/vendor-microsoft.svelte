<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc8h3_bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc8h3_bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:vendor-microsoft" {...props}></Icon>
