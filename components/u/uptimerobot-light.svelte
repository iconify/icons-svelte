<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4rsj3bvm.css';
import '../../css/o/oss8yqu8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q4rsj3bvm"/><circle class="oss8yqu8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptimerobot-light" {...props}></Icon>
