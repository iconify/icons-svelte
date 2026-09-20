<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j28299b9j.css';
import '../../css/v/vvnnjvbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j28299b9j"/><path class="vvnnjvbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:upload-alt-solid" {...props}></Icon>
