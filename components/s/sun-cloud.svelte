<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqqiq4boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qqqiq4boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sun-cloud" {...props}></Icon>
