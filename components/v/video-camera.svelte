<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asa8i895g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asa8i895g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:video-camera" {...props}></Icon>
