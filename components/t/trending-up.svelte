<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvaa8ubcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="jvaa8ubcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:trending-up" {...props}></Icon>
