<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yenqbtb5g.css';
import '../../css/g/ge98ujwjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yenqbtb5g"/><path class="ge98ujwjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-minus-filled" {...props}></Icon>
