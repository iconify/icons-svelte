<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u71pldtly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u71pldtly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:traffic-cone" {...props}></Icon>
