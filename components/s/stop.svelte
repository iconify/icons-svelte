<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-if3ugxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="x-if3ugxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:stop" {...props}></Icon>
