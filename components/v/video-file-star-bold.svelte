<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lphvcgben.css';
import '../../css/m/m2r9rjb4e.css';
import '../../css/o/o7yyb8b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lphvcgben"/><path class="m2r9rjb4e"/><path class="o7yyb8b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-file-star-bold" {...props}></Icon>
