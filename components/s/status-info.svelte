<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdm16pbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdm16pbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-info" {...props}></Icon>
