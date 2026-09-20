<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcknti30u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcknti30u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:run2" {...props}></Icon>
