<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm4bqebwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm4bqebwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:view-structure-down" {...props}></Icon>
