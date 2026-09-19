<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voayclbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="voayclbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-good-small" {...props}></Icon>
