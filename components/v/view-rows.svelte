<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf8pw_b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qf8pw_b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:view-rows" {...props}></Icon>
