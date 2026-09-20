<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrcz8lelj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrcz8lelj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xdb" {...props}></Icon>
