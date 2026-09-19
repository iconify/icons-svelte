<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yavt59bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yavt59bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:scion" {...props}></Icon>
