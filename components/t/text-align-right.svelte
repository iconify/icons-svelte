<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w__z_2btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w__z_2btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:text-align-right" {...props}></Icon>
