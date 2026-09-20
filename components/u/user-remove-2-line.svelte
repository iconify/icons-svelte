<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2o-rpepc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2o-rpepc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-remove-2-line" {...props}></Icon>
