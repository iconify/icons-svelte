<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys0ffgblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys0ffgblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sql-query" {...props}></Icon>
