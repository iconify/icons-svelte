<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og0d26bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og0d26bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:update" {...props}></Icon>
