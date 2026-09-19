<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw1zfl6mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw1zfl6mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:template" {...props}></Icon>
