<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij6y9bwyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ij6y9bwyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:search1api" {...props}></Icon>
