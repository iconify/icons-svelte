<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqn9w_jlc.css';
import '../../css/e/e2_8yl1ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dqn9w_jlc"/><path class="e2_8yl1ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:taco-48" {...props}></Icon>
