<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynl0eabys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynl0eabys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:star-outline" {...props}></Icon>
