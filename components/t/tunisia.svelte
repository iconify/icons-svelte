<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdftbpbaj.css';
import '../../css/w/wfcjrhbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="wdftbpbaj"/><path class="wfcjrhbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:tunisia" {...props}></Icon>
