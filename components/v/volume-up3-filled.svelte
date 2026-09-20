<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxlfg-bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxlfg-bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-up3-filled" {...props}></Icon>
