<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-k5ywbsm.css';
import '../../css/a/a1j4qjn6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="x-k5ywbsm"/><path class="a1j4qjn6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:xx-4x3" {...props}></Icon>
