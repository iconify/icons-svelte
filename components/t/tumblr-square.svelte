<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-296b9zl.css';
import '../../css/u/u0j55db0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-296b9zl"/><path class="u0j55db0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:tumblr-square" {...props}></Icon>
