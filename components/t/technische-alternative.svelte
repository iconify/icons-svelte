<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u99g9jbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u99g9jbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:technische-alternative" {...props}></Icon>
