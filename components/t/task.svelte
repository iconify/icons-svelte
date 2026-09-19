<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn4vqebsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pn4vqebsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:task" {...props}></Icon>
