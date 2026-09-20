<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jga_xuh6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jga_xuh6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:workflow-24" {...props}></Icon>
