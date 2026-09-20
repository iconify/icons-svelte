<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg9o65o-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zg9o65o-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rudder-fill" {...props}></Icon>
