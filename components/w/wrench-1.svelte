<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh0ehhbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh0ehhbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:wrench-1" {...props}></Icon>
