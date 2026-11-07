<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a501rabcl.css';
import '../../css/b/by_dfvbkj.css';
import '../../css/p/ppn0rybgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a501rabcl"/><path class="by_dfvbkj"/><path clip-rule="evenodd" class="ppn0rybgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-check-outline" {...props}></Icon>
