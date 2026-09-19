<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhd497buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":650,"height":679};
const content = `<path class="vhd497buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:ustream" {...props}></Icon>
