<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb435bcbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb435bcbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:steps" {...props}></Icon>
