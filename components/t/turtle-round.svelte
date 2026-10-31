<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esem8mbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esem8mbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:turtle-round" {...props}></Icon>
