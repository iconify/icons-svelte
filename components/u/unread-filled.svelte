<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt874mbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lt874mbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:unread-filled" {...props}></Icon>
