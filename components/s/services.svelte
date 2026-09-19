<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixs07e3on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixs07e3on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:services" {...props}></Icon>
