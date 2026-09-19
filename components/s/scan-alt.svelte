<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg2ekibvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg2ekibvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:scan-alt" {...props}></Icon>
