<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmkz1wbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmkz1wbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:talenthouse" {...props}></Icon>
