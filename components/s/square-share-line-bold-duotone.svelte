<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkwop1f3g.css';
import '../../css/p/pdyp1acvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkwop1f3g"/><path clip-rule="evenodd" class="pdyp1acvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-share-line-bold-duotone" {...props}></Icon>
