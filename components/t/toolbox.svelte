<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rneo-_btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rneo-_btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:toolbox" {...props}></Icon>
