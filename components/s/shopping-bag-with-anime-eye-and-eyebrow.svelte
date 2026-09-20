<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdi1gtbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xdi1gtbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-anime-eye-and-eyebrow" {...props}></Icon>
