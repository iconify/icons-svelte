<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne82av_3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ne82av_3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:schedules" {...props}></Icon>
