<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zobhzcaid.css';
import '../../css/z/zrdlp3d4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zobhzcaid"/><path class="zrdlp3d4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:ticket-duotone" {...props}></Icon>
