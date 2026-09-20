<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qes_-u4hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qes_-u4hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rss" {...props}></Icon>
