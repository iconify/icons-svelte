<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeim5hbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yeim5hbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sparks" {...props}></Icon>
