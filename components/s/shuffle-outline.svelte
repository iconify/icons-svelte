<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt4cuabsh.css';
import '../../css/s/s3xv2_brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bt4cuabsh"/><path clip-rule="evenodd" class="s3xv2_brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:shuffle-outline" {...props}></Icon>
