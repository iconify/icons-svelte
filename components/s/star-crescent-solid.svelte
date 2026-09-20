<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chq-6r-9v.css';
import '../../css/b/btvzwg_0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chq-6r-9v"/><path class="btvzwg_0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:star-crescent-solid" {...props}></Icon>
