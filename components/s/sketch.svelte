<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbhfagbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b fbhfagbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:sketch" {...props}></Icon>
