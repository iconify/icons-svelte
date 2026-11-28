<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtdqblb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtdqblb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:thumbs-down" {...props}></Icon>
