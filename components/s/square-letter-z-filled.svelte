<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdaup1bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdaup1bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-z-filled" {...props}></Icon>
