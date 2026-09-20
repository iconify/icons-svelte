<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb7byjbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lb7byjbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-drink-cup-with-steam" {...props}></Icon>
