<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhfg48bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhfg48bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:square-full" {...props}></Icon>
