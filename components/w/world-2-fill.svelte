<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvxj0b0tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvxj0b0tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:world-2-fill" {...props}></Icon>
