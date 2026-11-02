<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrs3eqc9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrs3eqc9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-left-collapse-fill" {...props}></Icon>
