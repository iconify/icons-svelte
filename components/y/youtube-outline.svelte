<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av_sbbbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="av_sbbbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:youtube-outline" {...props}></Icon>
