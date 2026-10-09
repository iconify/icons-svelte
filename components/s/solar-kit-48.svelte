<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8zhq3bqa.css';
import '../../css/k/k3148ab8q.css';
import '../../css/x/xmpbrx25v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e8zhq3bqa"/><path class="k3148ab8q"/><path class="xmpbrx25v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-kit-48" {...props}></Icon>
