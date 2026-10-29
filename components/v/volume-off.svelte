<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlzdue8eu.css';
import '../../css/u/uibgwrabt.css';
import '../../css/a/a2mdgrbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlzdue8eu wm-k"/><path class="uibgwrabt wm-k"/><path class="a2mdgrbxu wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:volume-off" {...props}></Icon>
