<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbos7x4cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nbos7x4cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:server-pbx-alt-filled" {...props}></Icon>
