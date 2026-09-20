<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm4_6m-0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm4_6m-0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-passenger" {...props}></Icon>
