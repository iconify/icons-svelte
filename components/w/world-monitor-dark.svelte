<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9t074brf.css';
import '../../css/v/v-7b52b6r.css';
import '../../css/x/xmmjaib5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9t074brf"/><path class="v-7b52b6r"/><circle class="xmmjaib5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:world-monitor-dark" {...props}></Icon>
