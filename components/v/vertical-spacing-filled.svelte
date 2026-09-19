<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr2ppd9zo.css';
import '../../css/g/goxr0e-pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr2ppd9zo"/><rect class="goxr0e-pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-spacing-filled" {...props}></Icon>
