<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbl7r9mon.css';
import '../../css/z/zvcrm1bfj.css';
import '../../css/g/g5vtw-iho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="kbl7r9mon"/><path class="zvcrm1bfj"/><path class="g5vtw-iho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:terminal-locked-24" {...props}></Icon>
