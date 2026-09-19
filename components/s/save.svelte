<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzfg9e1eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzfg9e1eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:save" {...props}></Icon>
