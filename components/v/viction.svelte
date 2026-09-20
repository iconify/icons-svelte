<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poh6isbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poh6isbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:viction" {...props}></Icon>
