<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn88ezbzu.css';
import '../../css/q/qklumbcjc.css';
import '../../css/s/semobrtpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wn88ezbzu"/><path class="qklumbcjc"/><path class="semobrtpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ship-48" {...props}></Icon>
