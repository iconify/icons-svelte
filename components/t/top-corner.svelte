<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiwllkblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiwllkblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:top-corner" {...props}></Icon>
