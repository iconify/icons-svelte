<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnz-81blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnz-81blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-warning" {...props}></Icon>
