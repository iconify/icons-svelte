<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ousr7gb-s.css';
import '../../css/j/j4j_tvbpu.css';
import '../../css/s/sof-_6mix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ousr7gb-s"/><path class="j4j_tvbpu"/><path class="sof-_6mix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:sidebar" {...props}></Icon>
