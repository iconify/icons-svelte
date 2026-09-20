<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5ejrebmz.css';
import '../../css/b/b1k5j-d7u.css';
import '../../css/e/e12tw0b8p.css';
import '../../css/q/qrrh5951r.css';
import '../../css/u/uymgdabjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b5ejrebmz"/><path class="b1k5j-d7u"/><path class="e12tw0b8p"/><path class="qrrh5951r"/><path class="uymgdabjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:vulcan-salute-2" {...props}></Icon>
