<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv_1wzb4e.css';
import '../../css/c/cwc7jqb5a.css';
import '../../css/i/irvj6xk3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dv_1wzb4e"/><path class="cwc7jqb5a"/><path class="irvj6xk3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:silo-media-server-dark" {...props}></Icon>
