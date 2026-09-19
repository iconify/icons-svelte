<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq33i5s8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq33i5s8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:terminal" {...props}></Icon>
