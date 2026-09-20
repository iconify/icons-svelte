<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwjddt0wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xwjddt0wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tag-filled" {...props}></Icon>
