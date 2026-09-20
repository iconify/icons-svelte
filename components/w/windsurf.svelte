<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw12u9--k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw12u9--k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:windsurf" {...props}></Icon>
