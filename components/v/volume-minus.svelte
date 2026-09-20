<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj88e2lso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj88e2lso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:volume-minus" {...props}></Icon>
