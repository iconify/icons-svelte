<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c49zb3b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c49zb3b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:text-wrap" {...props}></Icon>
