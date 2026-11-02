<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzeh9mbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzeh9mbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:surfboard-fill" {...props}></Icon>
