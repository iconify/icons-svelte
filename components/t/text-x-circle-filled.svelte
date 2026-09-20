<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4xqd7m7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4xqd7m7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-x-circle-filled" {...props}></Icon>
