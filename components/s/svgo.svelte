<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igrpvzb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igrpvzb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:svgo" {...props}></Icon>
