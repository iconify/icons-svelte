<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nillri43z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nillri43z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:wordpress" {...props}></Icon>
