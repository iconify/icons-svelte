<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbq477g4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wbq477g4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ssd-round-outline" {...props}></Icon>
