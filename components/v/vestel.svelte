<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c33elpbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c33elpbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vestel" {...props}></Icon>
