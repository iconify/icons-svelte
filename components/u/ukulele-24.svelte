<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k75k9-z_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k75k9-z_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ukulele-24" {...props}></Icon>
