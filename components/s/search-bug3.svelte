<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiq_uhhwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iiq_uhhwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:search-bug3" {...props}></Icon>
