<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkhs_xi9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkhs_xi9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-add-fill" {...props}></Icon>
