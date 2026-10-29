<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn7ih8b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn7ih8b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-alert-solid" {...props}></Icon>
