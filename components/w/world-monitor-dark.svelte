<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9t074brf.css';
import '../../css/o/o_5jqwb6l.css';
import '../../css/s/s8uw1xbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9t074brf"/><path class="o_5jqwb6l"/><circle class="s8uw1xbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:world-monitor-dark" {...props}></Icon>
