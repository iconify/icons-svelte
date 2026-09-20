<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkks6l3vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkks6l3vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:user-x-solid" {...props}></Icon>
