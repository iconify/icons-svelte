<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kryvvdb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kryvvdb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:traffic-cone" {...props}></Icon>
