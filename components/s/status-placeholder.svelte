<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je0er7b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="je0er7b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-placeholder" {...props}></Icon>
