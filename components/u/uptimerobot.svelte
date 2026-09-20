<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5lz9no8r.css';
import '../../css/b/b5b9_cc2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="a5lz9no8r"/><circle class="b5b9_cc2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptimerobot" {...props}></Icon>
