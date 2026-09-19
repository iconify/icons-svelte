<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqrmy-53b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqrmy-53b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:schedule-new" {...props}></Icon>
