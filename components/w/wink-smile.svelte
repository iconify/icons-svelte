<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s00y7mbtg.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/t/tk43u5bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s00y7mbtg"/><path class="bwibdw4bb"/><path class="tk43u5bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wink-smile" {...props}></Icon>
