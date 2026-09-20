<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usw_opafh.css';
import '../../css/s/s9jcc4brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usw_opafh"/><path class="s9jcc4brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:washing-hand-bold" {...props}></Icon>
