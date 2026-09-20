<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4s69vbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r4s69vbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:send" {...props}></Icon>
