<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxoahb_wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxoahb_wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trophy-alt" {...props}></Icon>
