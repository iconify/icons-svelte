<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqs6jwblf.css';
import '../../css/i/i2jdkabow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqs6jwblf secondary"/><path class="i2jdkabow primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vase-duo" {...props}></Icon>
