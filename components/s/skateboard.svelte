<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzq_jlble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzq_jlble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:skateboard" {...props}></Icon>
