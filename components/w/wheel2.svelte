<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8-yxwesq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8-yxwesq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wheel2" {...props}></Icon>
