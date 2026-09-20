<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-alhn0sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-alhn0sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:unlink" {...props}></Icon>
