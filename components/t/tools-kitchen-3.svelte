<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rudvr6l0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rudvr6l0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tools-kitchen-3" {...props}></Icon>
