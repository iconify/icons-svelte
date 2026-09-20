<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzievvboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzievvboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:users-solid" {...props}></Icon>
