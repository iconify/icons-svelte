<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmw7fe3td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pmw7fe3td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:text-edit" {...props}></Icon>
