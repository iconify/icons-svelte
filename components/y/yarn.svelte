<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/denkpb94f.css';
import '../../css/o/ouq9fewiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="denkpb94f"/><path class="ouq9fewiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:yarn" {...props}></Icon>
