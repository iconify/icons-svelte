<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzl_o7baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzl_o7baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sofa-solid" {...props}></Icon>
