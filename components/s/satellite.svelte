<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6nbwb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa6nbwb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:satellite" {...props}></Icon>
