<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu43gsb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tu43gsb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tomtom" {...props}></Icon>
