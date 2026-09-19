<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdssnbbom.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/q/q285h9bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdssnbbom"/><path class="bwibdw4bb"/><path class="q285h9bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:universal-access" {...props}></Icon>
