<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n62r27bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n62r27bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:user-minus-solid" {...props}></Icon>
