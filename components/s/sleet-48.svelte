<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qthvhvbbw.css';
import '../../css/s/swgrbdc6r.css';
import '../../css/o/o5prfsbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qthvhvbbw"/><path class="swgrbdc6r"/><path class="o5prfsbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sleet-48" {...props}></Icon>
