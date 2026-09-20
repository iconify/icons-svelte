<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqsb1e8mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqsb1e8mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:vk-alt" {...props}></Icon>
