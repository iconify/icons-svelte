<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm8445ilo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm8445ilo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ups" {...props}></Icon>
