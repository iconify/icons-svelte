<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiv-qtb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiv-qtb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:stop-circle-fill" {...props}></Icon>
