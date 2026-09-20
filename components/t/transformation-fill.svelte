<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjt97bc8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xjt97bc8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transformation-fill" {...props}></Icon>
