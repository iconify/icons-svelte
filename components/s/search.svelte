<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk5rwjmzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk5rwjmzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:search" {...props}></Icon>
