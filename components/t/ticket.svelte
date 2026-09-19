<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc01oya5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="kc01oya5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ticket" {...props}></Icon>
