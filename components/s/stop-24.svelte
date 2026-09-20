<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-n03pbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-n03pbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:stop-24" {...props}></Icon>
