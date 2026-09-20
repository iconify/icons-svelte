<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gznn9sbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gznn9sbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:sport-shoe" {...props}></Icon>
