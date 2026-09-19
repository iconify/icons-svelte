<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfxuosbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfxuosbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:tools" {...props}></Icon>
