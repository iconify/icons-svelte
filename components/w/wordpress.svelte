<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okamclltt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="okamclltt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:wordpress" {...props}></Icon>
