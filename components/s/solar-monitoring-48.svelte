<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xszfmab4u.css';
import '../../css/h/hutzz7vvf.css';
import '../../css/b/b-qq9xb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xszfmab4u"/><path class="hutzz7vvf"/><path class="b-qq9xb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-monitoring-48" {...props}></Icon>
