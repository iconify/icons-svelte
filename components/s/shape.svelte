<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bocvvbcei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":384};
const content = `<path class="bocvvbcei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:shape" {...props}></Icon>
