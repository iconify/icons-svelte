<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcrqbubeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dcrqbubeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spendspentspent-dark" {...props}></Icon>
