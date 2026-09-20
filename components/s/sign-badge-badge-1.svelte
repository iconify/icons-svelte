<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrfxpszrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrfxpszrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:sign-badge-badge-1" {...props}></Icon>
