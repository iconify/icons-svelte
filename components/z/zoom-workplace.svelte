<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fra1fsbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fra1fsbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:zoom-workplace" {...props}></Icon>
