<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy3hj8xrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oy3hj8xrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:viggle" {...props}></Icon>
