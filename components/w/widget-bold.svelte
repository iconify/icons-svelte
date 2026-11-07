<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yawhug1ht.css';
import '../../css/f/fuv2pzbjk.css';
import '../../css/b/b2f0rdb6m.css';
import '../../css/y/yi8dv1b1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yawhug1ht"/><path class="fuv2pzbjk"/><path class="b2f0rdb6m"/><path class="yi8dv1b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-bold" {...props}></Icon>
