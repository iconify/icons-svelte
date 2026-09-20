<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf7eihhbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf7eihhbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:step-forward" {...props}></Icon>
