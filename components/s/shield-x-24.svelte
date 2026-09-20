<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc8j9ubrc.css';
import '../../css/u/uxsu2sb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc8j9ubrc"/><path class="uxsu2sb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield-x-24" {...props}></Icon>
