<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meq_0c5ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="meq_0c5ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wallet-plus" {...props}></Icon>
