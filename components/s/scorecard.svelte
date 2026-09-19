<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiw01h8mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiw01h8mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:scorecard" {...props}></Icon>
