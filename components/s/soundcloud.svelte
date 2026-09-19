<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6oms2bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1280};
const content = `<path class="d6oms2bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:soundcloud" {...props}></Icon>
