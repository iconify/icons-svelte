<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwgnlkawf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwgnlkawf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shower-gel-line" {...props}></Icon>
