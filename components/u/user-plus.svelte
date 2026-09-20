<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bailacklh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bailacklh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:user-plus" {...props}></Icon>
