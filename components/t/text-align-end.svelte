<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f37g478bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f37g478bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-align-end" {...props}></Icon>
