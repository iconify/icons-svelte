<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9p861bjm.css';
import '../../css/b/b2y5zk0fk.css';
import '../../css/j/jqs9sql0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9p861bjm"/><path clip-rule="evenodd" class="b2y5zk0fk"/><path class="jqs9sql0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-cog-filled" {...props}></Icon>
