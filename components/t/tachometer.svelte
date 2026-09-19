<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os2lqsv0d.css';
import '../../css/i/intfgbexo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os2lqsv0d"/><path class="intfgbexo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tachometer" {...props}></Icon>
