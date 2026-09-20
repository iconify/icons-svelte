<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7w72dyhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7w72dyhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:writing-system-thai" {...props}></Icon>
