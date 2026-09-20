<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4wr9qy2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4wr9qy2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:user" {...props}></Icon>
