<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvbuhr78r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvbuhr78r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stethoscope-fill" {...props}></Icon>
