<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btp35gb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btp35gb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tornado" {...props}></Icon>
