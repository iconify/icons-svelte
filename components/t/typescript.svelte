<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd0eg4xnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd0eg4xnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:typescript" {...props}></Icon>
