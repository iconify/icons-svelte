<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox_3gkbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_3gkbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:slideshare" {...props}></Icon>
