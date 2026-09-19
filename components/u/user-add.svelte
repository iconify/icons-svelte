<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl4m8djlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl4m8djlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:user-add" {...props}></Icon>
