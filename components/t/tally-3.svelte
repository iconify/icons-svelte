<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmp9qmbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmp9qmbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-3" {...props}></Icon>
