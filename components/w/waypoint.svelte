<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg3fc5b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sg3fc5b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:waypoint" {...props}></Icon>
