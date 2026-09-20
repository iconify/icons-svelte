<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbl9r61qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbl9r61qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:spinner-alt" {...props}></Icon>
