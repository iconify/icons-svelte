<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kglf35eyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kglf35eyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tinygrad" {...props}></Icon>
