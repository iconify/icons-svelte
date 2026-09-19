<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-e9ybfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1-e9ybfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:translate-alt-filled" {...props}></Icon>
