<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lukals4wc.css';
import '../../css/u/u9zmojb0f.css';
import '../../css/k/kl2kn05lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lukals4wc"/><path class="u9zmojb0f"/><path class="kl2kn05lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sharkord" {...props}></Icon>
