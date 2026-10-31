<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfyz_vbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfyz_vbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-check-round" {...props}></Icon>
