<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y76tjhvwb.css';
import '../../css/e/ebn2v62aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y76tjhvwb"/><path class="ebn2v62aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rss-bridge" {...props}></Icon>
