<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqb6y59an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqb6y59an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wallet-check" {...props}></Icon>
