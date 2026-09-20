<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2g90nbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2g90nbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:uptobox" {...props}></Icon>
