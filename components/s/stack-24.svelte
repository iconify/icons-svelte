<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg_zrkbvf.css';
import '../../css/j/j525vvb7b.css';
import '../../css/s/s9rtedbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_zrkbvf"/><path class="j525vvb7b"/><path class="s9rtedbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:stack-24" {...props}></Icon>
