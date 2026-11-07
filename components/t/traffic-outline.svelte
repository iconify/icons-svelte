<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snl37hbbd.css';
import '../../css/r/rgo7s3bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snl37hbbd"/><path class="rgo7s3bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:traffic-outline" {...props}></Icon>
