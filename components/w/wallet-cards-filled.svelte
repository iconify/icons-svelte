<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvebsfbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvebsfbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wallet-cards-filled" {...props}></Icon>
