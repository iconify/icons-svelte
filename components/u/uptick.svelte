<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvbze2s-t.css';
import '../../css/j/j0zlpmbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvbze2s-t"/><path class="j0zlpmbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:uptick" {...props}></Icon>
