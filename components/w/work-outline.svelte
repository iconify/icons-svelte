<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_-qf_91f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_-qf_91f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:work-outline" {...props}></Icon>
