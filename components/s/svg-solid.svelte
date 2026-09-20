<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx4hw-btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kx4hw-btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:svg-solid" {...props}></Icon>
