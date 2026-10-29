<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd9e8th7d.css';
import '../../css/b/b0w0zoqxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd9e8th7d"/><path class="b0w0zoqxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:shield" {...props}></Icon>
