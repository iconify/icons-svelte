<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9y8g5y4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9y8g5y4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:schedule-play" {...props}></Icon>
