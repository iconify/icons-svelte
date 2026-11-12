<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqk752b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xqk752b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yoink-dark" {...props}></Icon>
