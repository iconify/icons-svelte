<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz64nmlvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz64nmlvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:svgtrace" {...props}></Icon>
