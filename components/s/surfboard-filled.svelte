<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk8oqf10s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk8oqf10s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:surfboard-filled" {...props}></Icon>
