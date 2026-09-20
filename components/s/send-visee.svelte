<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1mi8z8gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o1mi8z8gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:send-visee" {...props}></Icon>
