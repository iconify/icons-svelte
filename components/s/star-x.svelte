<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdb_vssxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdb_vssxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:star-x" {...props}></Icon>
