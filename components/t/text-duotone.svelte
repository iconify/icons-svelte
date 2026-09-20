<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywo665bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywo665bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:text-duotone" {...props}></Icon>
