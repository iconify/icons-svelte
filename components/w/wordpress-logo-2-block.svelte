<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-r1m6bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-r1m6bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wordpress-logo-2-block" {...props}></Icon>
